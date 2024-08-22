import math

def pizza_calculator():
    """Вычисляет общую площадь пиццы."""

    diameter = float(input("Введите диаметр пиццы в дюймах: "))
    quantity = int(input("Введите количество пицц: "))

    radius = diameter / 2
    area = math.pi * radius**2

    total_area = area * quantity

    print(f"Площадь одной пиццы: {area:.2f} квадратных дюймов")
    print(f"Общая площадь пиццы: {total_area:.2f} квадратных дюймов")

if __name__ == "__main__":
    pizza_calculator()
    
