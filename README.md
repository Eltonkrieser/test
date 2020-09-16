# src/AppBundle/Resources/config/validation.yml
AppBundle\Entity\Person:
    properties:
        siblings:
            - LessThan: 5
        age:
            - LessThan:
                value: 80
